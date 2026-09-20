<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw0f0ebnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw0f0ebnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:signal-alt" {...props}></Icon>
