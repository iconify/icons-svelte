<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzaed-0-h.css';
import '../../css/z/z709enohq.css';
import '../../css/u/uqivdzdek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uzaed-0-h"/><path class="z709enohq"/><path class="uqivdzdek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rov-48" {...props}></Icon>
