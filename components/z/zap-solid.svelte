<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v__cujb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v__cujb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zap-solid" {...props}></Icon>
