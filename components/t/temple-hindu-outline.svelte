<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqfy69bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqfy69bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:temple-hindu-outline" {...props}></Icon>
