<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0gb2qhkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0gb2qhkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:wasabi" {...props}></Icon>
