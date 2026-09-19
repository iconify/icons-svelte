<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sunnwjbfh.css';
import '../../css/s/sn5sf53te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sunnwjbfh"/><path class="sn5sf53te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:virtual-guest" {...props}></Icon>
