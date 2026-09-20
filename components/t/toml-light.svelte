<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdid5bc2g.css';
import '../../css/e/e_r59eb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sdid5bc2g"/><path class="e_r59eb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:toml-light" {...props}></Icon>
