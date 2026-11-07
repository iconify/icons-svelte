<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgzavdeog.css';
import '../../css/h/h5nyfzb8a.css';
import '../../css/i/i9po9cwhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgzavdeog"/><path class="h5nyfzb8a"/><path clip-rule="evenodd" class="i9po9cwhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:turntable-music-note-bold" {...props}></Icon>
