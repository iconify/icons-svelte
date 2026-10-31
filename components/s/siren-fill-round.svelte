<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utpq3jyxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utpq3jyxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:siren-fill-round" {...props}></Icon>
