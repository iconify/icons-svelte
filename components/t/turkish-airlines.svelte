<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okz34ybum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okz34ybum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:turkish-airlines" {...props}></Icon>
