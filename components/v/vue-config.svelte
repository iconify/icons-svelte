<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me00cjb6q.css';
import '../../css/d/dezr6ts0k.css';
import '../../css/w/wdholibql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="me00cjb6q"/><path class="dezr6ts0k"/><path class="wdholibql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vue-config" {...props}></Icon>
