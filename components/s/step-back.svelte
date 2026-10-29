<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slmn96b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slmn96b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:step-back" {...props}></Icon>
