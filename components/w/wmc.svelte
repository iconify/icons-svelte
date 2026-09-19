<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6y36oe8d.css';
import '../../css/b/biue_cm9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="q6y36oe8d"/><path class="biue_cm9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:wmc" {...props}></Icon>
