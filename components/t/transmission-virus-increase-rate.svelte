<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o804cb_ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o804cb_ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-increase-rate" {...props}></Icon>
