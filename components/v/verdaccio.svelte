<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmzp2srzw.css';
import '../../css/a/avn_ef2yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmzp2srzw"/><path class="avn_ef2yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:verdaccio" {...props}></Icon>
