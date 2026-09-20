<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsoddbbnl.css';
import '../../css/w/w-6tn9btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsoddbbnl"/><path class="w-6tn9btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:transfer-pictures-sent" {...props}></Icon>
