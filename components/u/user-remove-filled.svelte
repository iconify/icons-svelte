<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktdokp0kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktdokp0kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-remove-filled" {...props}></Icon>
