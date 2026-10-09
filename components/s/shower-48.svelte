<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch7fqmebm.css';
import '../../css/v/vh9btobqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ch7fqmebm"/><path class="vh9btobqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shower-48" {...props}></Icon>
