<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rix1rccmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rix1rccmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:salad" {...props}></Icon>
