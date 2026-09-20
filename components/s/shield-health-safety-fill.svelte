<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyyulzbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dyyulzbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:shield-health-safety-fill" {...props}></Icon>
