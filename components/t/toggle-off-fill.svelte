<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt9gqfocz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lt9gqfocz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:toggle-off-fill" {...props}></Icon>
