<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb87oacvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb87oacvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:t-box-line" {...props}></Icon>
