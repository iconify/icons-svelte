<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6s34zqwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6s34zqwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-door" {...props}></Icon>
