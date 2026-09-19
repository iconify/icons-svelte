<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkuzq1bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fkuzq1bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:squares-2x2" {...props}></Icon>
