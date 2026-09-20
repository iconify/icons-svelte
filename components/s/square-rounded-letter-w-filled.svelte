<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjd2aeb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjd2aeb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-rounded-letter-w-filled" {...props}></Icon>
