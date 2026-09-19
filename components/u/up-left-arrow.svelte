<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qscg1vb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qscg1vb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:up-left-arrow" {...props}></Icon>
