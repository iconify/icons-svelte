<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic8csbqvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic8csbqvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:steamdeck" {...props}></Icon>
