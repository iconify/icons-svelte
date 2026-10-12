<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw8ygub3e.css';
import '../../css/k/k7-izcbee.css';
import '../../css/e/e_r9uibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw8ygub3e"/><path class="k7-izcbee"/><path class="e_r9uibzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-check-filled" {...props}></Icon>
