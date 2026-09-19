<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkljblwjh.css';
import '../../css/n/nb72zx0al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkljblwjh"/><path class="nb72zx0al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:school" {...props}></Icon>
