<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mte_34_1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mte_34_1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:up-small-line" {...props}></Icon>
