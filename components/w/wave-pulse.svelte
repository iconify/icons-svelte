<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyv8nfhqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyv8nfhqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wave-pulse" {...props}></Icon>
