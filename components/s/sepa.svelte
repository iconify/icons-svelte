<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfke22dsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfke22dsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sepa" {...props}></Icon>
