<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6116jr8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6116jr8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-checkered" {...props}></Icon>
