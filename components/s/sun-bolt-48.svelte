<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f70j8yk4i.css';
import '../../css/m/mytw5ubob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f70j8yk4i"/><path class="mytw5ubob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-bolt-48" {...props}></Icon>
