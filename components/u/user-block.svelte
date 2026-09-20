<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt3bd-w9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vt3bd-w9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-block" {...props}></Icon>
