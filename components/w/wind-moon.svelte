<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyc9efbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyc9efbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:wind-moon" {...props}></Icon>
