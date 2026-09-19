<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksclpdbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksclpdbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tim-logo" {...props}></Icon>
