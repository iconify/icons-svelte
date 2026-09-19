<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzeq6nw0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fzeq6nw0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rows-two-filled" {...props}></Icon>
