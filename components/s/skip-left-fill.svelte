<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imo3q5bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imo3q5bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:skip-left-fill" {...props}></Icon>
