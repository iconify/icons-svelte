<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6kwe5_4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6kwe5_4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:substack-filled" {...props}></Icon>
