<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoirqcbtc.css';
import '../../css/o/ojb5ey7sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yoirqcbtc"/><circle class="ojb5ey7sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:user-group-ltr" {...props}></Icon>
