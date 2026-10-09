<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb3dfkb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jb3dfkb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-cog-48-bold" {...props}></Icon>
