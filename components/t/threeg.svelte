<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-aiilfxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":832};
const content = `<path class="u-aiilfxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:threeg" {...props}></Icon>
