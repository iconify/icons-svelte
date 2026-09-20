<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubzx9fbaa.css';
import '../../css/d/dlqc4jbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ubzx9fbaa"/><path class="dlqc4jbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:unread-16" {...props}></Icon>
