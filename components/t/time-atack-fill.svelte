<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo6voubbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yo6voubbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:time-atack-fill" {...props}></Icon>
