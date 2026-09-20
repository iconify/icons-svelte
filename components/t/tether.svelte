<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or-9fcc4e.css';
import '../../css/t/tsrj5epuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":339.43,"height":295.27};
const content = `<path class="or-9fcc4e"/><path class="tsrj5epuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tether" {...props}></Icon>
