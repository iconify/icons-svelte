<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf3tq_caf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf3tq_caf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:test-tube" {...props}></Icon>
