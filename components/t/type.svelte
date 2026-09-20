<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb8-6ypcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb8-6ypcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:type" {...props}></Icon>
