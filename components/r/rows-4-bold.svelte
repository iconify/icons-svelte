<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf5tgeqen.css';
import '../../css/g/g7lf42b8j.css';
import '../../css/k/kjee7xvdg.css';
import '../../css/j/jqlk-kbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rf5tgeqen"/><path class="g7lf42b8j"/><path class="kjee7xvdg"/><path class="jqlk-kbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rows-4-bold" {...props}></Icon>
