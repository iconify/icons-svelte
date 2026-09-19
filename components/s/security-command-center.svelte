<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k188_sbpi.css';
import '../../css/f/f7bma5brt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k188_sbpi"/><circle class="f7bma5brt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:security-command-center" {...props}></Icon>
