<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw96a2bzf.css';
import '../../css/y/yc4kfubew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer gw96a2bzf"/><path class="duoicon-primary-layer yc4kfubew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:world" {...props}></Icon>
