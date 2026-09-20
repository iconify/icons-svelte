<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5_uczi6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o5_uczi6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:social-stumbleupon" {...props}></Icon>
