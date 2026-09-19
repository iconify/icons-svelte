<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmzeugb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jmzeugb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:vagrant" {...props}></Icon>
