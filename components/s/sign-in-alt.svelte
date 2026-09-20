<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imylg0bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imylg0bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sign-in-alt" {...props}></Icon>
