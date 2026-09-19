<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g86q6cbgz.css';
import '../../css/s/sygzb3b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g86q6cbgz"/><path class="sygzb3b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:safety-outlined" {...props}></Icon>
