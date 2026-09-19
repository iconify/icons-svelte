<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omcviu_cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omcviu_cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:smiling-face-fill" {...props}></Icon>
