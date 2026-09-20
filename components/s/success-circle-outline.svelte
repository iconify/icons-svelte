<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-gf19h6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-gf19h6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:success-circle-outline" {...props}></Icon>
