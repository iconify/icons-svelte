<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiygavb6e.css';
import '../../css/a/atbdsbcmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiygavb6e"/><path class="atbdsbcmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:themes" {...props}></Icon>
