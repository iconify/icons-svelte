<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lql2hob3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lql2hob3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scooter2" {...props}></Icon>
