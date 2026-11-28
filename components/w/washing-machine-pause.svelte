<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqa7g4vnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqa7g4vnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:washing-machine-pause" {...props}></Icon>
