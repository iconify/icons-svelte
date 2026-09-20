<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj6brm96n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj6brm96n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:undertake-transaction-filled" {...props}></Icon>
