<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk_k-5bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk_k-5bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:send-hor" {...props}></Icon>
