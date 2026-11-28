<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt9w2ci5j.css';
import '../../css/r/ryi59f59s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt9w2ci5j secondary"/><path class="primary ryi59f59s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sparkle-duo" {...props}></Icon>
