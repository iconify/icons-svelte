<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x__nbyi8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x__nbyi8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:test-tube-filled" {...props}></Icon>
