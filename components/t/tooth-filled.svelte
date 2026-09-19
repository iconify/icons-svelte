<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvg0ib-hb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvg0ib-hb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tooth-filled" {...props}></Icon>
