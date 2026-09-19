<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-hj12b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-hj12b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:transmission-virus-float-wind" {...props}></Icon>
