<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebrfcd7vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ebrfcd7vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-cog-outline" {...props}></Icon>
