<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk88s11pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk88s11pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:subscriptions-created" {...props}></Icon>
