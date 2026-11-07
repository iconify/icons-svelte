<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii1sy95ok.css';
import '../../css/a/au09dfbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1sy95ok"/><path class="au09dfbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-academic-cap-bold" {...props}></Icon>
