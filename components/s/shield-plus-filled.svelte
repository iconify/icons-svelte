<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhrz9cckz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhrz9cckz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shield-plus-filled" {...props}></Icon>
