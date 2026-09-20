<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkj1g9zqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkj1g9zqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:servbay" {...props}></Icon>
