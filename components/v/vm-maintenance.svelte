<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1d-02bug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1d-02bug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:vm-maintenance" {...props}></Icon>
