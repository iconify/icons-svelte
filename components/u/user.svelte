<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/d/dqyuhxbem.css';
import '../../css/n/nyh5boz2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="dqyuhxbem"/><ellipse transform="rotate(-90 12 16)" class="nyh5boz2s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:user" {...props}></Icon>
