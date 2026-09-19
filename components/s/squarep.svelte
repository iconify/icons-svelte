<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1mfq9ajy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="c1mfq9ajy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squarep" {...props}></Icon>
