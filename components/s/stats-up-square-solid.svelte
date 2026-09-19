<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qap_r6b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qap_r6b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:stats-up-square-solid" {...props}></Icon>
