<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxnj3wrkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxnj3wrkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-two-solid" {...props}></Icon>
