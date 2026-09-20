<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpexxw0-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vpexxw0-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:sign-in" {...props}></Icon>
