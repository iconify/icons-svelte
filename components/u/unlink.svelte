<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uld0v671t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uld0v671t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:unlink" {...props}></Icon>
