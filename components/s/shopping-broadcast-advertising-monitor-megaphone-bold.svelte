<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5npjlsdw.css';
import '../../css/v/v_drcnb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5npjlsdw"/><path class="v_drcnb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-broadcast-advertising-monitor-megaphone-bold" {...props}></Icon>
