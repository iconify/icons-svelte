<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i67o6e_jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i67o6e_jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shield" {...props}></Icon>
