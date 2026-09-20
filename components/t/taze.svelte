<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b85kfggca.css';
import '../../css/d/dqv-n8bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b85kfggca"/><path class="dqv-n8bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:taze" {...props}></Icon>
