<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u665ban.css';
import '../../css/e/ev_angbau.css';
import '../../css/f/f4slk7mgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="ev_angbau"/><path class="f4slk7mgd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:share-link" {...props}></Icon>
