<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypjqnzb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="ypjqnzb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:wacom-tablet" {...props}></Icon>
