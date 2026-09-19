<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_lhkccrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_lhkccrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wallet-cards" {...props}></Icon>
