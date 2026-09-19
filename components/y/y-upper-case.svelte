<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii_t20l9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":524,"height":735};
const content = `<path class="ii_t20l9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:y-upper-case" {...props}></Icon>
