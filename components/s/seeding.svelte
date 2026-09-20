<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzz0u3bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzz0u3bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:seeding" {...props}></Icon>
