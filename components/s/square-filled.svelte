<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krb-eh9nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krb-eh9nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:square-filled" {...props}></Icon>
