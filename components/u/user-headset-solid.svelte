<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk_6gseuv.css';
import '../../css/j/jtop0ctzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk_6gseuv"/><path class="jtop0ctzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:user-headset-solid" {...props}></Icon>
