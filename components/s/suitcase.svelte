<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqgwv0bzt.css';
import '../../css/y/yi6ar83pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uqgwv0bzt"/><path class="yi6ar83pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:suitcase" {...props}></Icon>
