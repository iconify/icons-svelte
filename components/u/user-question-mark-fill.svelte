<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hta1nyqdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hta1nyqdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:user-question-mark-fill" {...props}></Icon>
