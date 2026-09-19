<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haddg8b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="haddg8b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:users-group-filled" {...props}></Icon>
