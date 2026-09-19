<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilq4mj0ny.css';
import '../../css/a/agps2ol2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilq4mj0ny"/><path class="agps2ol2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:text-to-speech" {...props}></Icon>
