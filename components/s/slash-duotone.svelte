<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oznlfac6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oznlfac6x primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:slash-duotone" {...props}></Icon>
