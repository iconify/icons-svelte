<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cshuyzyel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cshuyzyel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:subtitles-bold" {...props}></Icon>
