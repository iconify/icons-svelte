<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddn7u078w.css';
import '../../css/d/d1guyq2pd.css';
import '../../css/n/nmfn-h5ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddn7u078w"/><path class="d1guyq2pd"/><path class="nmfn-h5ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-bold-duotone" {...props}></Icon>
