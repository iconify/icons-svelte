<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2yxnrbti.css';
import '../../css/s/suyzx0beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m2yxnrbti"/><path class="suyzx0beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tag-20" {...props}></Icon>
