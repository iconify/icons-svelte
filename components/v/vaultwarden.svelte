<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq_iiuban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq_iiuban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vaultwarden" {...props}></Icon>
