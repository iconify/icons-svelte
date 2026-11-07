<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_-x04hkk.css';
import '../../css/l/lo2kz2b5c.css';
import '../../css/r/rtrsrablt.css';
import '../../css/k/kirw6ebyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_-x04hkk"/><path class="lo2kz2b5c"/><path class="rtrsrablt"/><path clip-rule="evenodd" class="kirw6ebyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skateboarding-round-outline" {...props}></Icon>
