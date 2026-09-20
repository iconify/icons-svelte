<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eexulhiqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eexulhiqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:x-24" {...props}></Icon>
