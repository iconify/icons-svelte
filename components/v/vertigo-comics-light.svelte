<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7m_-rsmc.css';
import '../../css/g/go7xeob4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g7m_-rsmc"/><path class="go7xeob4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vertigo-comics-light" {...props}></Icon>
