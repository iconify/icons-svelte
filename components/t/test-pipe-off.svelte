<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9v-njkwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9v-njkwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:test-pipe-off" {...props}></Icon>
