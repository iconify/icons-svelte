<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouhh3jbqt.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qzwcluezf.css';
import '../../css/t/tw4-rib7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouhh3jbqt secondary"/><g class="dt0cm9dhy primary"><path class="qzwcluezf"/><path class="tw4-rib7g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-dot-duo" {...props}></Icon>
