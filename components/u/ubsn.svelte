<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj32hac5p.css';
import '../../css/b/bdvnvrbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj32hac5p"/><path class="bdvnvrbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ubsn" {...props}></Icon>
