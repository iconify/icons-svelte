<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt01zo83t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jt01zo83t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-bold" {...props}></Icon>
