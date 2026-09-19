<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0hd_7v4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0hd_7v4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:slack-filled" {...props}></Icon>
