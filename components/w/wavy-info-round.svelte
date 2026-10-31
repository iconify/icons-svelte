<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqo-nvbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqo-nvbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wavy-info-round" {...props}></Icon>
