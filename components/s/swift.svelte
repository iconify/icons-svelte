<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq5rus7wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kq5rus7wf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:swift" {...props}></Icon>
