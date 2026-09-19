<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6-p4wl9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6-p4wl9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:shield" {...props}></Icon>
