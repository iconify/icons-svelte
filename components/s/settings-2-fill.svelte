<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-0dcx9cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-0dcx9cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-2-fill" {...props}></Icon>
