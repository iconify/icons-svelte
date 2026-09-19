<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0vlk6j2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0vlk6j2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trash-alt" {...props}></Icon>
