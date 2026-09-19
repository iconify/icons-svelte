<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7u3b2bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7u3b2bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:text-color" {...props}></Icon>
